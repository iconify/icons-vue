<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vodrtwb3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vodrtwb3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:baseball-filled" /></template>
