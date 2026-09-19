<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwup8r63e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwup8r63e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-filled" /></template>
