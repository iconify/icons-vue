<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwvk9yb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwvk9yb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrow-right-circle" /></template>
