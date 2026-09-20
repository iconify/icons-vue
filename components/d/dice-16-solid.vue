<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scn5v8bhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="scn5v8bhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dice-16-solid" /></template>
