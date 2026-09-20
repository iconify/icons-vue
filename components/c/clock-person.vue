<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-7ueksdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a-7ueksdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:clock-person" /></template>
