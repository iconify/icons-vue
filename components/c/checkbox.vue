<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efz_1fkfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="efz_1fkfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:checkbox" /></template>
