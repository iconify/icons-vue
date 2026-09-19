<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac7du0n2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac7du0n2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:chevron-double-down-outline" /></template>
