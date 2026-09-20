<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aey68mb3i.css';
import '../../css/y/ynooprbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aey68mb3i"/><path class="ynooprbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-nine-light" /></template>
