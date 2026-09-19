<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv6fjxbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="jv6fjxbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:hi5" /></template>
