<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvnnzl8ms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vvnnzl8ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:bicycle-16-solid" /></template>
