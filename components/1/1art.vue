<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_qlbdb_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_qlbdb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:1art" /></template>
