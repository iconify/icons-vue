<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joaz6-u6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="joaz6-u6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:direction-right-01" /></template>
