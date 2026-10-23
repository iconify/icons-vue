<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkry21_9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkry21_9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layers-plus" /></template>
