<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rea5ecj9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rea5ecj9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:archive-alt-line" /></template>
