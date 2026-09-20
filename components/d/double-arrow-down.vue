<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abki_wbql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="abki_wbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:double-arrow-down" /></template>
