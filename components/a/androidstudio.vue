<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uix0dubku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uix0dubku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:androidstudio" /></template>
