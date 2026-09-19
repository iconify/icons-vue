<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epoweac4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="epoweac4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:dice-1" /></template>
