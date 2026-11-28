<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uchy9pbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uchy9pbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-up-circle-solid" /></template>
