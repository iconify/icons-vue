<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nln9_m3-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nln9_m3-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:guitar-pick-filled" /></template>
