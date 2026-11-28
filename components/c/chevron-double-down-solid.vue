<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emug_9xpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emug_9xpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-double-down-solid" /></template>
