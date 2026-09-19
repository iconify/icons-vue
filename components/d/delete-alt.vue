<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efu0u547c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efu0u547c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:delete-alt" /></template>
