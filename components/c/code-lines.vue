<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-ali6sre.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-ali6sre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:code-lines" /></template>
