<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns2zw5bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns2zw5bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alltrails" /></template>
