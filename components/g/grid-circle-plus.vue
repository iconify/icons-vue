<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb9f_wazq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb9f_wazq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-circle-plus" /></template>
