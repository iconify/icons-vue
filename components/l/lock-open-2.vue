<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8omlku6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s8omlku6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:lock-open-2" /></template>
