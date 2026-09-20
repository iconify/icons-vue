<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pik0u_bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pik0u_bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down2" /></template>
