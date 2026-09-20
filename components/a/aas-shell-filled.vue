<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usw10sb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usw10sb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-shell-filled" /></template>
