<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqgebmbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqgebmbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flower-fill-round" /></template>
