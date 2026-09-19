<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv82bmbkc.css';
import '../../css/x/xb-3e0r0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yv82bmbkc"/><path class="xb-3e0r0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:boo" /></template>
