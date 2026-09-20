<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4q581bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4q581bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cup-off" /></template>
