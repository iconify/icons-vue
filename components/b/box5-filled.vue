<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdcmtdids.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdcmtdids"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box5-filled" /></template>
