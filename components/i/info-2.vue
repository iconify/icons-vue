<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbpuy8oju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zbpuy8oju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:info-2" /></template>
