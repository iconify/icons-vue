<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpf1zacks.css';
import '../../css/n/nqe79lxrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kpf1zacks"/><path class="nqe79lxrn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:health-hospital-building-2" /></template>
