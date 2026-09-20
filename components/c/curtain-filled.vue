<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds42oz0-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ds42oz0-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:curtain-filled" /></template>
