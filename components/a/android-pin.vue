<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-9123c1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o-9123c1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-pin" /></template>
