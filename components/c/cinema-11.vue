<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnfizcb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="qnfizcb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:cinema-11" /></template>
