<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfqyf4b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wfqyf4b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:border-dashed" /></template>
