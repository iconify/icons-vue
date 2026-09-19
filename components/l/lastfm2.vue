<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5f75abtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n5f75abtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:lastfm2" /></template>
