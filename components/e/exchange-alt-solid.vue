<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0_rdmbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y0_rdmbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:exchange-alt-solid" /></template>
