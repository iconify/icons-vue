<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kk5-6fd1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kk5-6fd1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:double-caret-up-circle-solid" /></template>
