<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9wu50bnx.css';
import '../../css/a/a__ik5b7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9wu50bnx"/><path class="a__ik5b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cisco-anyconnect" /></template>
