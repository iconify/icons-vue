<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tm7-k-41s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tm7-k-41s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gamepad-1-filled" /></template>
