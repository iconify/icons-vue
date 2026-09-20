<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcib6zbdi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcib6zbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:blood-minus-outline" /></template>
