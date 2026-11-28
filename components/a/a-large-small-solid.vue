<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5a9jpbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5a9jpbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:a-large-small-solid" /></template>
