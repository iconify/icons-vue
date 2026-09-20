<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_ac9abqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ac9abqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fire2-filled" /></template>
