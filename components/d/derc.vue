<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmj18yb6f.css';
import '../../css/t/tfqe-pf5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmj18yb6f"/><path class="tfqe-pf5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:derc" /></template>
