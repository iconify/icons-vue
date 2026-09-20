<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keqss3brm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keqss3brm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-deezer" /></template>
