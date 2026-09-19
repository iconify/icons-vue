<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6013-iew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b6013-iew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:briefcase" /></template>
