<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2j-smfbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2j-smfbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:eenvo-dark" /></template>
