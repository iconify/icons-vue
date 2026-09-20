<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snv45gbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snv45gbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:anonymous" /></template>
