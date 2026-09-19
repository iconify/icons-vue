<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/col2zcbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="col2zcbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up" /></template>
