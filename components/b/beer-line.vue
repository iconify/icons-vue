<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9tnc6n-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9tnc6n-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:beer-line" /></template>
