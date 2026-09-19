<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zutc_xbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zutc_xbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-remove-circle" /></template>
