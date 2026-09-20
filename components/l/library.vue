<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tprn2zk0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tprn2zk0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:library" /></template>
