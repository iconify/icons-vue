<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oat_n_6bp.css';
import '../../css/q/qbbwyjbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oat_n_6bp"/><path class="qbbwyjbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-truck-filled" /></template>
