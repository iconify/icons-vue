<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay8hjugra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay8hjugra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:fold-horizontal" /></template>
