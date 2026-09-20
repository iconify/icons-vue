<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi04vibzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="hi04vibzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:bolt-3" /></template>
