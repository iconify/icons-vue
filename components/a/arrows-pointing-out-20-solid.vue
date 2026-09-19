<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aybjhpbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aybjhpbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrows-pointing-out-20-solid" /></template>
