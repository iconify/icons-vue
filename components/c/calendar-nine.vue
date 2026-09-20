<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aey68mb3i.css';
import '../../css/y/ynooprbfx.css';
import '../../css/y/yc1hb9b0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aey68mb3i"/><path class="ynooprbfx"/><path clip-rule="evenodd" class="yc1hb9b0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-nine" /></template>
