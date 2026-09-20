<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co17elbuu.css';
import '../../css/o/oh7_w2b4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co17elbuu"/><path class="oh7_w2b4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:alert-alarm-bell" /></template>
