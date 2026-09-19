<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as0sge_bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as0sge_bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-compare-filled" /></template>
