<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jcgiwkbay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jcgiwkbay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:biltema" /></template>
