<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrzqhjbcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrzqhjbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:asterisk" /></template>
