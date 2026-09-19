<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ploom_bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ploom_bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-appstore" /></template>
