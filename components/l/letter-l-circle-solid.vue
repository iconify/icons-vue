<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adh7oxwzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adh7oxwzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-l-circle-solid" /></template>
