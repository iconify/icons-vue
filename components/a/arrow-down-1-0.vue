<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsykozb_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsykozb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-1-0" /></template>
