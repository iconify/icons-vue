<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4i02jbgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j4i02jbgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:azuracast-dark" /></template>
