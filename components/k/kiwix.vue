<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lblsu7bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lblsu7bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kiwix" /></template>
