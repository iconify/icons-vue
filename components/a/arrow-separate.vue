<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6hm_db6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6hm_db6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:arrow-separate" /></template>
