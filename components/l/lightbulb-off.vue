<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xujn9gwht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xujn9gwht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lightbulb-off" /></template>
