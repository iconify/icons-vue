<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9mt1pbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l9mt1pbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:eye-none" /></template>
