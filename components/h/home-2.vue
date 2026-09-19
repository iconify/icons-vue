<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3_mn_6bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3_mn_6bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:home-2" /></template>
