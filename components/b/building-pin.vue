<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks3m9vbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks3m9vbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:building-pin" /></template>
