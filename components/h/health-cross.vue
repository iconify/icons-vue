<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2-40acus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n2-40acus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:health-cross" /></template>
