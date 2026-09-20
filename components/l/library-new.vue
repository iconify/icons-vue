<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihd7gsbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihd7gsbsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:library-new" /></template>
