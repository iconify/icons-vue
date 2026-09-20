<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0pqhea9a.css';
import '../../css/z/zoadec5pq.css';
import '../../css/z/zb2w8cc6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0pqhea9a"/><path class="zoadec5pq"/><path class="zb2w8cc6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:imgur" /></template>
