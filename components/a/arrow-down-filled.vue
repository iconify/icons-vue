<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs0on26ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs0on26ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down-filled" /></template>
