<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4s149y6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4s149y6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:location-filled" /></template>
