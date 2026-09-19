<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xaf3epb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xaf3epb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:archive" /></template>
