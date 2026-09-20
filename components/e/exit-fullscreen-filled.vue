<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g947x_bkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g947x_bkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:exit-fullscreen-filled" /></template>
