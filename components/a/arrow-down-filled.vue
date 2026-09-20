<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iq4no3lcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iq4no3lcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:arrow-down-filled" /></template>
