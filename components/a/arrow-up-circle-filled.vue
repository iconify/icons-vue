<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5yuqmboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5yuqmboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-circle-filled" /></template>
