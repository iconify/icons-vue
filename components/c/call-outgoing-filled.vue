<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfkk76bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfkk76bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:call-outgoing-filled" /></template>
