<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwan62b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bwan62b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:certshell-light" /></template>
