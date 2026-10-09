<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7q9a2bck.css';
import '../../css/v/vzivax-kb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7q9a2bck"/><path class="vzivax-kb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-up-right-20" /></template>
