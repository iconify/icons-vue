<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbdjepb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbdjepb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googlechronicle" /></template>
