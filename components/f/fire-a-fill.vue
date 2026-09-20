<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3vic4b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3vic4b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:fire-a-fill" /></template>
