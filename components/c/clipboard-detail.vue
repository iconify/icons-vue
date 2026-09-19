<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqbi2s1wa.css';
import '../../css/p/pa14hnb-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqbi2s1wa"/><path class="pa14hnb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clipboard-detail" /></template>
