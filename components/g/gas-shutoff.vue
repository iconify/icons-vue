<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzk7_ll8g.css';
import '../../css/e/ejog3cncc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dzk7_ll8g"/><path class="ejog3cncc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:gas-shutoff" /></template>
