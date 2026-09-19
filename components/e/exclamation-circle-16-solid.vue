<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb3mgp2iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hb3mgp2iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:exclamation-circle-16-solid" /></template>
