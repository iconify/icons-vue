<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xud0d_adg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xud0d_adg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:info-circle" /></template>
