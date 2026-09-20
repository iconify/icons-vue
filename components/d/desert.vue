<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsno0ormi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsno0ormi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:desert" /></template>
