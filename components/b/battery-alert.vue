<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgt41rbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgt41rbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:battery-alert" /></template>
