<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_e_8cb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_e_8cb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:image-circle-line" /></template>
