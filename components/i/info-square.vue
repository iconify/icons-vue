<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v88_xacul.css';
import '../../css/b/bn6ebpb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v88_xacul"/><path class="bn6ebpb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:info-square" /></template>
