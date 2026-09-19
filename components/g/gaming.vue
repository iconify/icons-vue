<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpfg_4bzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpfg_4bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gaming" /></template>
