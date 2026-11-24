<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx50cdblo.css';
import '../../css/q/qlt_8zq6z.css';
import '../../css/g/gqc9d0bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx50cdblo"/><path class="qlt_8zq6z"/><path class="gqc9d0bgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:goal-filled" /></template>
