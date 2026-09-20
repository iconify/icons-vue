<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7xf0gald.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7xf0gald"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cockpit-light" /></template>
