<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uas6i0ufn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uas6i0ufn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:drumpad" /></template>
