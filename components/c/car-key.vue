<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty5wgbcxn.css';
import '../../css/d/di8rvibxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty5wgbcxn"/><path class="di8rvibxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:car-key" /></template>
