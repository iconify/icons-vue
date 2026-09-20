<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2hsmse-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="a2hsmse-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:certificate" /></template>
