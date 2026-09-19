<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxv55ebri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxv55ebri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:help-questionmark" /></template>
