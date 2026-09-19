<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8k1kk5iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8k1kk5iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:exclamation-circle" /></template>
