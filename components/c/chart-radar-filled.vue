<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7kcxrbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7kcxrbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chart-radar-filled" /></template>
