<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2zw_0hnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s2zw_0hnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:ban" /></template>
