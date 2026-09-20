<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw-7h4bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kw-7h4bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forward-right2" /></template>
