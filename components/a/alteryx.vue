<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmrgo_bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmrgo_bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alteryx" /></template>
