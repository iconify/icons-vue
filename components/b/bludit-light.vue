<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5xvncr9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i5xvncr9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bludit-light" /></template>
