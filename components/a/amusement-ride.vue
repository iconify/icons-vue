<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/suo_2083c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="suo_2083c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:amusement-ride" /></template>
