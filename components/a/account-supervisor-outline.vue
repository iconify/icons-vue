<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkvr25bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkvr25bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-supervisor-outline" /></template>
