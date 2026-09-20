<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7y-pvuqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7y-pvuqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:frappe-hr-light" /></template>
