<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx33ejloy.css';
import '../../css/g/g4efp7-2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx33ejloy"/><path class="g4efp7-2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:heroku" /></template>
