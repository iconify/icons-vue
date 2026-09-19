<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzq91cpzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzq91cpzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-double-down" /></template>
