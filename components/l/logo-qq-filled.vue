<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgxo9gb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="lgxo9gb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-qq-filled" /></template>
