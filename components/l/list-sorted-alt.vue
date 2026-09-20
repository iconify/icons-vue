<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prjy6udbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="prjy6udbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:list-sorted-alt" /></template>
