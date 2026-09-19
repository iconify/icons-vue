<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j02vs_14r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j02vs_14r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:flag-alt" /></template>
