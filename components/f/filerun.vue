<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-gr0fbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-gr0fbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filerun" /></template>
