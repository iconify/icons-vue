<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-q2yr28x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j-q2yr28x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:logo-venmo" /></template>
