<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9nwk9bcv.css';
import '../../css/u/u42idu8ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="g9nwk9bcv"/><path class="u42idu8ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-vertical-end-filled" /></template>
