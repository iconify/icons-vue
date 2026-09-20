<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8fl3zb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8fl3zb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:electron" /></template>
