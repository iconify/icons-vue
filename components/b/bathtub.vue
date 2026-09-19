<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3brg2cab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3brg2cab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bathtub" /></template>
