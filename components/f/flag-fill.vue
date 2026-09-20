<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmbv34e3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmbv34e3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flag-fill" /></template>
