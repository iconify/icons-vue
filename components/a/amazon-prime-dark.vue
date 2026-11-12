<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-u8tebtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-u8tebtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-prime-dark" /></template>
