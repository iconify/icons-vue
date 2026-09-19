<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu1i2oh_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iu1i2oh_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:frame" /></template>
