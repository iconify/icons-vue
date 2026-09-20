<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ur4f7_bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur4f7_bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-caret-up-filled" /></template>
