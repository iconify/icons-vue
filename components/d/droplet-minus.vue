<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yur87nwye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yur87nwye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:droplet-minus" /></template>
