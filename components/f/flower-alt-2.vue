<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-i0pbve.css';
import '../../css/z/zura7v_tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7-i0pbve"/><path class="zura7v_tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flower-alt-2" /></template>
