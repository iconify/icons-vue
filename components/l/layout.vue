<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc599u7ic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nc599u7ic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:layout" /></template>
