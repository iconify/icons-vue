<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw0nn2bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw0nn2bxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-arrow-path-solid" /></template>
