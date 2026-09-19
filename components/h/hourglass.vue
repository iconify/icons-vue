<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvpw1ac4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":512};
const content = `<path class="mvpw1ac4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hourglass" /></template>
