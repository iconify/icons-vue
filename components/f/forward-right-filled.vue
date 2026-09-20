<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5lxj0zxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5lxj0zxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-right-filled" /></template>
