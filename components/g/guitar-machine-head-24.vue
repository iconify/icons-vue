<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aaizi4b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aaizi4b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:guitar-machine-head-24" /></template>
