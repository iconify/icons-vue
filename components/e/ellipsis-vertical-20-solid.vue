<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ocn9i_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i0ocn9i_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:ellipsis-vertical-20-solid" /></template>
