<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpp-e2bmy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dpp-e2bmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:lpt" /></template>
