<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5s79wans.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5s79wans"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:layout-panel-right" /></template>
