<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7om_9bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7om_9bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:crop-alt" /></template>
