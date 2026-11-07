<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl4bbtw5c.css';
import '../../css/y/ynwkrvbew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl4bbtw5c"/><path class="ynwkrvbew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-left-bold" /></template>
