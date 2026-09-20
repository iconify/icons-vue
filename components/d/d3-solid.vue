<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-k6kc-pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="x-k6kc-pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:d3-solid" /></template>
