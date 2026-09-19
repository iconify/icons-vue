<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbd0fnbds.css';
import '../../css/s/sk6tzx05l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbd0fnbds"/><path class="sk6tzx05l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:computer-retro" /></template>
