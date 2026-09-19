<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbm47jbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pbm47jbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:asterisk" /></template>
