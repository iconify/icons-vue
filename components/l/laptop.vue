<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op92b2h4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op92b2h4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:laptop" /></template>
