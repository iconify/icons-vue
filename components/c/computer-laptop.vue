<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd_9dubqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd_9dubqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:computer-laptop" /></template>
