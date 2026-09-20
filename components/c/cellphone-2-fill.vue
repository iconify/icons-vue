<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywkuy3bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywkuy3bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-2-fill" /></template>
