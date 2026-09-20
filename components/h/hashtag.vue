<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-pmrl3-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-pmrl3-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hashtag" /></template>
