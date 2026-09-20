<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8zsfrlau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8zsfrlau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-slash-sharp-fill" /></template>
