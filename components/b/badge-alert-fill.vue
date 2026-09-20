<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av1mmm5yj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="av1mmm5yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:badge-alert-fill" /></template>
