<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wraso3b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wraso3b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:ear-speciality-solid" /></template>
