<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odvk9h54r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odvk9h54r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds" /></template>
