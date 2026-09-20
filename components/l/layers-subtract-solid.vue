<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j20ns8dno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="j20ns8dno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:layers-subtract-solid" /></template>
