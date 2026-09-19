<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbrt54buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbrt54buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:bus" /></template>
