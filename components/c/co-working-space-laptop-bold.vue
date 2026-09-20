<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu1bc8bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu1bc8bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:co-working-space-laptop-bold" /></template>
