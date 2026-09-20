<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idxmc4bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idxmc4bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:coder" /></template>
