<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mssm-8b3t.css';
import '../../css/n/n5rw468eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mssm-8b3t"/><path class="n5rw468eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-out-down-left-stroke-square" /></template>
