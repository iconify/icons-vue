<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d66mew_du.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d66mew_du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:down-arrow-alt" /></template>
