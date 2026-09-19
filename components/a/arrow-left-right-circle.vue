<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpz-9jmja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dpz-9jmja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-left-right-circle" /></template>
