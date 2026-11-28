<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibi5hccgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ibi5hccgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:license-plate-thin" /></template>
