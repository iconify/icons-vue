<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m30rb2h_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m30rb2h_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:external-link" /></template>
