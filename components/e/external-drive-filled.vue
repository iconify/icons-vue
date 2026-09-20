<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvlmg9bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvlmg9bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:external-drive-filled" /></template>
