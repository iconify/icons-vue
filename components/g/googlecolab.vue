<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3fifvbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3fifvbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlecolab" /></template>
