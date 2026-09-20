<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihphb4blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihphb4blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:lazyvim" /></template>
