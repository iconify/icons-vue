<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar2gpjbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ar2gpjbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:magento" /></template>
