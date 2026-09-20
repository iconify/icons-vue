<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpupycbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpupycbgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:accenture" /></template>
