<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rztg2463w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rztg2463w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:lettered-list" /></template>
