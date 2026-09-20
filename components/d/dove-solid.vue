<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmb1xtbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kmb1xtbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:dove-solid" /></template>
