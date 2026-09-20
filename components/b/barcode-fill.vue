<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxubx6b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxubx6b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:barcode-fill" /></template>
