<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9dfu13yp.css';
import '../../css/b/bn6ebpb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9dfu13yp"/><path class="bn6ebpb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-right-stroke-square" /></template>
