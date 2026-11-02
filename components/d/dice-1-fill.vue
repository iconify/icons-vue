<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv7mh-bsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv7mh-bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dice-1-fill" /></template>
