<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvntfobza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvntfobza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-alt-3" /></template>
