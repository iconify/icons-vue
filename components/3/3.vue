<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dx5403b3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":772};
const content = `<path class="dx5403b3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:3" /></template>
