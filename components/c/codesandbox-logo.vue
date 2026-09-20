<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx981cbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mx981cbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:codesandbox-logo" /></template>
