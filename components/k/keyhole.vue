<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egm_2b38y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="egm_2b38y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:keyhole" /></template>
