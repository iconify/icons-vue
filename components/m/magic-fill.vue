<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3k-ncbdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3k-ncbdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:magic-fill" /></template>
