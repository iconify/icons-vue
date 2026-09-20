<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv4z9efcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv4z9efcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-tinder-filled" /></template>
