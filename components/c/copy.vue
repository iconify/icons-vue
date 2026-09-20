<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ge7wz3biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ge7wz3biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:copy" /></template>
