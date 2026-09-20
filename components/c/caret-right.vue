<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3j4blber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3j4blber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:caret-right" /></template>
