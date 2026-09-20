<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-kw0fbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x-kw0fbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bug" /></template>
