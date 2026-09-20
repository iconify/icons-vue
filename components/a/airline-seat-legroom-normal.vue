<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay3ubnumw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay3ubnumw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:airline-seat-legroom-normal" /></template>
