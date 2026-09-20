<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk7og29zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7og29zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-output-bold" /></template>
