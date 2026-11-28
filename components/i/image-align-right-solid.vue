<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-5p2lb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-5p2lb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:image-align-right-solid" /></template>
