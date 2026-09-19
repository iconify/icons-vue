<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hitd8xbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hitd8xbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-trending-down" /></template>
