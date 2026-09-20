<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy_a9mbnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qy_a9mbnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-top-right" /></template>
