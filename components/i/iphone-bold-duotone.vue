<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyz0sxbtx.css';
import '../../css/g/g773-itfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyz0sxbtx"/><path class="g773-itfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:iphone-bold-duotone" /></template>
