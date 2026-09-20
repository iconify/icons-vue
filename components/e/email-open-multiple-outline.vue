<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu_2z9bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nu_2z9bjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:email-open-multiple-outline" /></template>
