<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nozaz7b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nozaz7b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ai2" /></template>
