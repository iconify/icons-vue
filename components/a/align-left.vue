<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b41cz12cc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b41cz12cc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:align-left" /></template>
