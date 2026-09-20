<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk7uk6brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7uk6brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:badge-cc-filled" /></template>
