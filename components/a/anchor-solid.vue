<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz-zpsb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nz-zpsb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:anchor-solid" /></template>
