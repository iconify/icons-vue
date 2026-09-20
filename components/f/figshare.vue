<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrjn6xbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jrjn6xbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:figshare" /></template>
