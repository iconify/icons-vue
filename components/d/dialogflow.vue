<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwb61c__y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwb61c__y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dialogflow" /></template>
