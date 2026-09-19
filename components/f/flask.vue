<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgay69b_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1024};
const content = `<path class="sgay69b_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:flask" /></template>
