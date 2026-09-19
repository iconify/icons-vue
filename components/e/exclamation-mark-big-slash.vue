<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyv5spbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyv5spbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:exclamation-mark-big-slash" /></template>
