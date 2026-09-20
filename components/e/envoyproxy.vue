<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd8zf1-gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd8zf1-gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:envoyproxy" /></template>
