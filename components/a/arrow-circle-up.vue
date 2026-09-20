<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxsoy8glv.css';
import '../../css/q/q098jibdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxsoy8glv"/><path class="q098jibdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-up" /></template>
