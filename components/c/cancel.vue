<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3cw-hawx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3cw-hawx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:cancel" /></template>
