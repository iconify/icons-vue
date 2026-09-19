<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojm54hbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojm54hbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-exit" /></template>
