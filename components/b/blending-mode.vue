<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql-f45b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ql-f45b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:blending-mode" /></template>
