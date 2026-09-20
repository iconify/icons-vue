<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7blleqsn.css';
import '../../css/u/uj_xhacmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7blleqsn"/><path class="uj_xhacmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:go-pro-bold" /></template>
