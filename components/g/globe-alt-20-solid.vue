<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2p5n4w2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2p5n4w2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-alt-20-solid" /></template>
