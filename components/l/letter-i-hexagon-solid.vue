<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqooofg9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqooofg9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-i-hexagon-solid" /></template>
