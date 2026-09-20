<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vubu2cchl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vubu2cchl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alarm-pause-filled" /></template>
