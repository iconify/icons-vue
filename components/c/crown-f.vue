<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfamv3h8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="zfamv3h8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:crown-f" /></template>
