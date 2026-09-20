<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w34otac-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w34otac-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:award-filled" /></template>
