<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxn26ubua.css';
import '../../css/i/inhewssvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxn26ubua"/><path class="inhewssvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:buildings" /></template>
