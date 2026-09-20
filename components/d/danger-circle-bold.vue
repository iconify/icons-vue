<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de5-ioblz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="de5-ioblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:danger-circle-bold" /></template>
