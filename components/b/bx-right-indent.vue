<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afqitcbed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afqitcbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-right-indent" /></template>
