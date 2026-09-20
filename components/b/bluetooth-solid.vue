<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8vwweh-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="x8vwweh-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bluetooth-solid" /></template>
