<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpl-7jcme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zpl-7jcme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:clear-filter" /></template>
