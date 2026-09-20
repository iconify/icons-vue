<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1q4ppb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1q4ppb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:droplet" /></template>
