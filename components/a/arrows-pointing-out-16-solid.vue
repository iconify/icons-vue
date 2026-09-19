<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc667f1qx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kc667f1qx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-pointing-out-16-solid" /></template>
