<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jly_eg06t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="jly_eg06t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:emo-devil" /></template>
