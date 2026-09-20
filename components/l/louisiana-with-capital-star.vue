<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8xpn1iix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m8xpn1iix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:louisiana-with-capital-star" /></template>
