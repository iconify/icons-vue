<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksv6oqjmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ksv6oqjmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:apple" /></template>
