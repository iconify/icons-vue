<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3t-t7xoa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n3t-t7xoa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-double-up-solid" /></template>
