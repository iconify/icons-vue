<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4_gqn-ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_gqn-ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dtube" /></template>
