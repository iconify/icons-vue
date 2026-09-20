<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/giq6r0irk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="giq6r0irk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:battery-mid" /></template>
