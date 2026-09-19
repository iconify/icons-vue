<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_18fpb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="v_18fpb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:external" /></template>
