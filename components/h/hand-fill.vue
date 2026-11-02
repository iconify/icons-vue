<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjbkop1ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjbkop1ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-fill" /></template>
