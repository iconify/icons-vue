<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqw4fpf6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqw4fpf6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-step" /></template>
