<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpryfp0ky.css';
import '../../css/o/omiz2rshg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bpryfp0ky"/><path class="omiz2rshg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:globe" /></template>
