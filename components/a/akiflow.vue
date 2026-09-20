<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxcd9eb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxcd9eb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:akiflow" /></template>
