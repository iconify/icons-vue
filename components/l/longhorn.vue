<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqr0i-kdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqr0i-kdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:longhorn" /></template>
