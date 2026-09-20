<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koeqcs6me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koeqcs6me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:face-id" /></template>
