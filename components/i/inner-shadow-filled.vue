<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egeq1474n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b egeq1474n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:inner-shadow-filled" /></template>
