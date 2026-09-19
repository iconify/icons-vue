<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bjgc9gb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":24};
const content = `<path class="bjgc9gb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:foursquare" /></template>
