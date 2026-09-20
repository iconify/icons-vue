<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg-_syi2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg-_syi2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-upper-sharp" /></template>
