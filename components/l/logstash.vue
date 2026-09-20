<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9pme_s9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9pme_s9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:logstash" /></template>
