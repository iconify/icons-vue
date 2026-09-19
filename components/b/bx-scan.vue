<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbf7gxbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbf7gxbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-scan" /></template>
