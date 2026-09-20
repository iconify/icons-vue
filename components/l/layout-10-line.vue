<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw1e9dbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw1e9dbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-10-line" /></template>
