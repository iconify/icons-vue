<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwwrox8vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lwwrox8vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bicycle" /></template>
