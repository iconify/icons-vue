<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilm43_ows.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ilm43_ows"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:bridge" /></template>
