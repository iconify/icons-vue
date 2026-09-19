<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj10chahh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj10chahh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fast-forward-circle-filled" /></template>
