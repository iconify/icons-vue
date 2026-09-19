<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7sfj1b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n7sfj1b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-notifications" /></template>
