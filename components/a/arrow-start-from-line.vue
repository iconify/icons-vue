<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqn1sqbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqn1sqbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:arrow-start-from-line" /></template>
