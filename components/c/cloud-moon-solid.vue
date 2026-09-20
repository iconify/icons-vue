<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs6qk0bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs6qk0bhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cloud-moon-solid" /></template>
