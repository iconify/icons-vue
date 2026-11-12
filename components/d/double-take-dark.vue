<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jht319lou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jht319lou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:double-take-dark" /></template>
