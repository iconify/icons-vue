<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7vp-0tdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7vp-0tdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-arke" /></template>
