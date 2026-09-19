<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igbjqgb3u.css';
import '../../css/s/sdwvt0b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="igbjqgb3u"/><path class="sdwvt0b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-desktop" /></template>
