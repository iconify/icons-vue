<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct7v-bboa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct7v-bboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:equal-approximately-sharp" /></template>
