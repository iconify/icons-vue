<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpfogblvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="bpfogblvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angle-up" /></template>
