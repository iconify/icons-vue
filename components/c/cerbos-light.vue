<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qktj-0d9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qktj-0d9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cerbos-light" /></template>
