<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezpmhobgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezpmhobgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:cone" /></template>
