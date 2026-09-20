<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beeswymqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beeswymqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:location-off-target-bold" /></template>
