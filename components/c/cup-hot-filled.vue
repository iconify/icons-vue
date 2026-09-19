<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unactzblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unactzblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cup-hot-filled" /></template>
