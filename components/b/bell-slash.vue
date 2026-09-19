<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiripzknj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xiripzknj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:bell-slash" /></template>
