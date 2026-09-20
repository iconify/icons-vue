<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp2pmrbnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp2pmrbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:format-italic" /></template>
