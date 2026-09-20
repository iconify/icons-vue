<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tate_tblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tate_tblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-filled" /></template>
