<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v63eijmiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="v63eijmiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:clapperboard" /></template>
