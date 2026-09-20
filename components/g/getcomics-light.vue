<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7hw7w48k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7hw7w48k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:getcomics-light" /></template>
