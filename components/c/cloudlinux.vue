<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw_e8kbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw_e8kbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cloudlinux" /></template>
