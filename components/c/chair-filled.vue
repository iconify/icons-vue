<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlpswnbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlpswnbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chair-filled" /></template>
