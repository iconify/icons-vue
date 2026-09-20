<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck8zkmb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8zkmb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:direct-left-filled" /></template>
