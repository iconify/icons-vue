<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noh1fb71d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="noh1fb71d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:inv" /></template>
