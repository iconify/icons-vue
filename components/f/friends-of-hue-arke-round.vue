<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2ncilpqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2ncilpqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-arke-round" /></template>
