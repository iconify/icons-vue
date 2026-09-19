<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxwbsu80r.css';
import '../../css/x/xxyrztbdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxwbsu80r"/><path class="xxyrztbdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-left-circle-filled" /></template>
