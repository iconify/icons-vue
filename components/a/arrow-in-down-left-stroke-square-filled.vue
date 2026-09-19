<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_pgce4lp.css';
import '../../css/p/pn-6xpb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_pgce4lp"/><path class="pn-6xpb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-left-stroke-square-filled" /></template>
