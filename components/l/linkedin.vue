<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-2yo-qdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="m-2yo-qdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:linkedin" /></template>
