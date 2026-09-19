<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgh1gibyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgh1gibyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cheese-filled" /></template>
