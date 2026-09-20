<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eabl2c-zp.css';
import '../../css/l/lncpo0b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="eabl2c-zp"/><path class="lncpo0b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:coins" /></template>
