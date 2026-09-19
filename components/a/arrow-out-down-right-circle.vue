<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-gja2bhg.css';
import '../../css/v/vnep0m7rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-gja2bhg"/><path class="vnep0m7rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-right-circle" /></template>
