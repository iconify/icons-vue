<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbvcxwbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbvcxwbif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:intr" /></template>
