<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goc6or3vc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="goc6or3vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:door-closed-locked" /></template>
