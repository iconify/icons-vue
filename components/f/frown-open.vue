<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9xru4bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="f9xru4bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:frown-open" /></template>
