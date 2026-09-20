<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh4qmdb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zh4qmdb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:longread" /></template>
