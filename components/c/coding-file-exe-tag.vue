<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_e5embpi.css';
import '../../css/z/z-1o8dzhg.css';
import '../../css/y/yjv1a9s6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k_e5embpi"/><path clip-rule="evenodd" class="z-1o8dzhg"/><path class="yjv1a9s6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:coding-file-exe-tag" /></template>
