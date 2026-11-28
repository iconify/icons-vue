<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac09f8epz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac09f8epz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:garage-open-solid" /></template>
