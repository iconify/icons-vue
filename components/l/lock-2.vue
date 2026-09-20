<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzk6pyl2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pzk6pyl2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:lock-2" /></template>
