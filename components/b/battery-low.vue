<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmqw-b0ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jmqw-b0ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:battery-low" /></template>
