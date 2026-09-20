<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqmbhv_3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqmbhv_3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrow-nested" /></template>
