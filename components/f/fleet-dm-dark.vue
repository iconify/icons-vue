<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjd7c4bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sjd7c4bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fleet-dm-dark" /></template>
