<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il39xh8sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="il39xh8sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:link-break-2" /></template>
