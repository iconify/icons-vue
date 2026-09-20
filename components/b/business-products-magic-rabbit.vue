<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt6wc-5ul.css';
import '../../css/i/iopdlzu5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zt6wc-5ul"/><path class="iopdlzu5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-magic-rabbit" /></template>
