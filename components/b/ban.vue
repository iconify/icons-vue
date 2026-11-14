<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv_4w2mzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv_4w2mzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ban" /></template>
