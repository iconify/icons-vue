<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfx_deblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="gfx_deblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:flask" /></template>
