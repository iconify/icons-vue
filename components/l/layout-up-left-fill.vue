<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt_s0ux-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt_s0ux-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:layout-up-left-fill" /></template>
