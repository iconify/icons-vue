<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyu5cbb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyu5cbb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-off-filled" /></template>
