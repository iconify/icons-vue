<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlzj64_zc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="mlzj64_zc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:digging" /></template>
