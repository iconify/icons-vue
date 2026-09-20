<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyak7sb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyak7sb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:banknote" /></template>
