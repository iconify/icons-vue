<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jayvw56hs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jayvw56hs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gitconnected" /></template>
