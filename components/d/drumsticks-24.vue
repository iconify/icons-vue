<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnncbwbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnncbwbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:drumsticks-24" /></template>
