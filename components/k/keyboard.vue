<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa3e_ihor.css';
import '../../css/s/ss1-wab0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa3e_ihor"/><path class="ss1-wab0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:keyboard" /></template>
