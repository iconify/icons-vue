<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqtc13b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xqtc13b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hotel-one-star-solid" /></template>
