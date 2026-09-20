<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmk7s0b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmk7s0b-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:bars" /></template>
