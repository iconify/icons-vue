<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6vv8jbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l6vv8jbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:left-solid" /></template>
