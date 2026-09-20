<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbm4ihbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jbm4ihbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:dots-horizontal" /></template>
