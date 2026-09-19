<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw8fk__of.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw8fk__of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple-iphone" /></template>
