<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-pv_7kao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a-pv_7kao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bucket-paint" /></template>
