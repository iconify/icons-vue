<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcism7j2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="vcism7j2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-down" /></template>
