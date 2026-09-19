<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjtl1l1wp.css';
import '../../css/b/bvlxd1b5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rjtl1l1wp"/><path class="bvlxd1b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-citrix-daas" /></template>
