<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-v909bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-v909bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:key-01" /></template>
