<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehs20_byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ehs20_byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:connect-contacts" /></template>
