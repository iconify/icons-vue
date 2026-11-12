<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b09u8ms8j.css';
import '../../css/u/u3jwqf4_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b09u8ms8j"/><path class="u3jwqf4_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:aliexpress-dark" /></template>
