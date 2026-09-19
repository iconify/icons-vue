<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fws7bbc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fws7bbc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bridge" /></template>
