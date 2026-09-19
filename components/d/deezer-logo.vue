<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw76jf7vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xw76jf7vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:deezer-logo" /></template>
