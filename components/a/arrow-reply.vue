<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr4b4bdaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr4b4bdaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-reply" /></template>
