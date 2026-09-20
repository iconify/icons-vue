<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1ncy95lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ncy95lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fast-forward" /></template>
