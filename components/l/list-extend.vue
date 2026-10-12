<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smlq9pall.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smlq9pall"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:list-extend" /></template>
