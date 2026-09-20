<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgwvj6b2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgwvj6b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:left-to-right-text-direction" /></template>
