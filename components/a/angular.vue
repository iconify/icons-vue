<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksox703bk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ksox703bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:angular" /></template>
