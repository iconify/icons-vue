<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5p02fbjy.css';
import '../../css/p/p_qjcl89l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a5p02fbjy"/><path class="p_qjcl89l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-prodect-diamond" /></template>
