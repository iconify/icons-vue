<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si5p7gb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si5p7gb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-upload" /></template>
