<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjthz755z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rjthz755z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:lock" /></template>
