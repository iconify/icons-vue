<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqotro3ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iqotro3ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-lock" /></template>
