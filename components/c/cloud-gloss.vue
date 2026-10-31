<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ufo1c2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6ufo1c2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-gloss" /></template>
