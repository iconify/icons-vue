<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkak67_rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkak67_rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-o" /></template>
