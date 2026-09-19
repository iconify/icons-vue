<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d045_fbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="d045_fbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:globe-asia" /></template>
