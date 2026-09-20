<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1jfhgh5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1jfhgh5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-ordered-sharp" /></template>
