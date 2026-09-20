<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw4uepb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw4uepb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:jump-off" /></template>
