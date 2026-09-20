<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkti4bbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xkti4bbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gatsbyjs-solid" /></template>
