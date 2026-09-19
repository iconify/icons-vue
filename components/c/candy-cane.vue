<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms3g9iieh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ms3g9iieh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:candy-cane" /></template>
