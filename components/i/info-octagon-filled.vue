<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ych81ffjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ych81ffjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:info-octagon-filled" /></template>
