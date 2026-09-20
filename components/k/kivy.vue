<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnhsm5wjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnhsm5wjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:kivy" /></template>
