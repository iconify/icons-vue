<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1y2cwd5s.css';
import '../../css/x/xxvlnybzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="k1y2cwd5s"/><path class="xxvlnybzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-4-solid" /></template>
