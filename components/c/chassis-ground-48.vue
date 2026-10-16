<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqsth4bzo.css';
import '../../css/n/ng_o9qbxw.css';
import '../../css/r/rnqgbobut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yqsth4bzo"/><path class="ng_o9qbxw"/><path class="rnqgbobut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chassis-ground-48" /></template>
