<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t80w8jedb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t80w8jedb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-question-fill" /></template>
