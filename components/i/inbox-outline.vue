<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvw4fsblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvw4fsblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:inbox-outline" /></template>
