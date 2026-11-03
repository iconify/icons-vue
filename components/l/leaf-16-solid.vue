<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn0m4nbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xn0m4nbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:leaf-16-solid" /></template>
