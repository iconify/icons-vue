<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl7231b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl7231b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-4-fill" /></template>
