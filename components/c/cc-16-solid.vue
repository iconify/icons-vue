<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1verfsgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w1verfsgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cc-16-solid" /></template>
