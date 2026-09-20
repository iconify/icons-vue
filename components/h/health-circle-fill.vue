<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-bbp7lwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bbp7lwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:health-circle-fill" /></template>
