<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfs3-mmpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfs3-mmpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:chevrons-up-down" /></template>
