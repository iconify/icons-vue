<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_bf30izc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":643,"height":696};
const content = `<path class="v_bf30izc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bold" /></template>
