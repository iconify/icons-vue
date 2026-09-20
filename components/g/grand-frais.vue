<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfg7h4bnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfg7h4bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:grand-frais" /></template>
