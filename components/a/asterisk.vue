<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of9ca_blq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="of9ca_blq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:asterisk" /></template>
