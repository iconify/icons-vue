<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sak19mmbt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sak19mmbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:chevron-up" /></template>
