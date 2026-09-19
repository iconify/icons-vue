<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx3ff8hyy.css';
import '../../css/y/y_b4318bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx3ff8hyy"/><path class="y_b4318bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:date" /></template>
