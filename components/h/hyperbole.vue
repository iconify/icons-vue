<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8-yh8lxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8-yh8lxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:hyperbole" /></template>
