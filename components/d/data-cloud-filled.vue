<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loevw9_ih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loevw9_ih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:data-cloud-filled" /></template>
