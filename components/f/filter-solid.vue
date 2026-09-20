<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9qtfr36x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9qtfr36x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:filter-solid" /></template>
