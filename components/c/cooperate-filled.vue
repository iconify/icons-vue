<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md2z_6kln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md2z_6kln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:cooperate-filled" /></template>
