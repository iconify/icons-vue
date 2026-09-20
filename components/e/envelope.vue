<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt_il320v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qt_il320v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:envelope" /></template>
