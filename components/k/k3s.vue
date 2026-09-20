<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy2k2q1_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy2k2q1_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:k3s" /></template>
