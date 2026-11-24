<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2m_w_n-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2m_w_n-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:carets-to-axis-horizontal-filled" /></template>
