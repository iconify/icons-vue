<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-55vfbsm.css';
import '../../css/c/cwu-c8bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-55vfbsm"/><path class="cwu-c8bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:fish" /></template>
