<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltm588bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltm588bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:joomla" /></template>
