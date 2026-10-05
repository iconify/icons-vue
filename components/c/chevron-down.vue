<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm0_39fsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm0_39fsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:chevron-down" /></template>
