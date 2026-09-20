<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckyq5qvae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckyq5qvae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:at-solid" /></template>
