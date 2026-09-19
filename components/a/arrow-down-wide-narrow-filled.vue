<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tod_2acqn.css';
import '../../css/h/hj1bo3bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tod_2acqn"/><path class="hj1bo3bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-wide-narrow-filled" /></template>
