<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m38pw-bkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m38pw-bkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:hand" /></template>
