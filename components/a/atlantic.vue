<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_8lbpb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_8lbpb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:atlantic" /></template>
