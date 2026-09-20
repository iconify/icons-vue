<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijbz8-bgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="ijbz8-bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:first" /></template>
