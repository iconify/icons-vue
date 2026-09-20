<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq6avqzec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vq6avqzec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:consistency-check" /></template>
