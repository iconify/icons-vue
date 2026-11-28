<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ni8h9jbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ni8h9jbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-lock" /></template>
