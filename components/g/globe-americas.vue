<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc8sjpsgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="wc8sjpsgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:globe-americas" /></template>
