<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/niu_geqxg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niu_geqxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:badge-alert" /></template>
