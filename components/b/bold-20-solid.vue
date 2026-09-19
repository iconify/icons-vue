<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfrvambcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wfrvambcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bold-20-solid" /></template>
