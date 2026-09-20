<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxttq7g5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxttq7g5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:location-solid" /></template>
