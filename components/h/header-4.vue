<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgve9iglu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-7};
const content = `<path class="vgve9iglu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:header-4" /></template>
