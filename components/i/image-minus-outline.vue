<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_o_b_b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_o_b_b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:image-minus-outline" /></template>
