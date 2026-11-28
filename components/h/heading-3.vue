<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq657hbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq657hbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heading-3" /></template>
