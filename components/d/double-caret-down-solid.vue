<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rr-3xacjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rr-3xacjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-down-solid" /></template>
