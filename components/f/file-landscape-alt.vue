<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw003mslz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw003mslz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-landscape-alt" /></template>
