<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d52at5ban.css';
import '../../css/b/bn6ebpb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d52at5ban"/><path class="bn6ebpb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-stroke-square" /></template>
