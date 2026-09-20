<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhogn0bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhogn0bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:caldotcom" /></template>
