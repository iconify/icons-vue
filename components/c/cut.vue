<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv41ofcxd.css';
import '../../css/b/bvlph1xti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv41ofcxd"/><path class="bvlph1xti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cut" /></template>
