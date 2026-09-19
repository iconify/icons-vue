<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/poz3ywv6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poz3ywv6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:clipboard-clean-outline" /></template>
