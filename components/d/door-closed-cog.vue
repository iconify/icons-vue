<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmvcb9bxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmvcb9bxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:door-closed-cog" /></template>
