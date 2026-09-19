<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnywrch1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnywrch1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:feather-alt-filled" /></template>
