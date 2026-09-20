<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s03_qnhzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="s03_qnhzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:even" /></template>
