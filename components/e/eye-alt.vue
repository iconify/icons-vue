<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0u5bhb-g.css';
import '../../css/x/x5shryb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0u5bhb-g"/><path class="x5shryb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-alt" /></template>
