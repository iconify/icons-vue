<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e65egtbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e65egtbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-check-filled" /></template>
