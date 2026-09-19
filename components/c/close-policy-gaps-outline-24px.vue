<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvv7_nbuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvv7_nbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:close-policy-gaps-outline-24px" /></template>
