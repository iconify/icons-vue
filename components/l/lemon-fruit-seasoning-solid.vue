<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztked6bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ztked6bew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:lemon-fruit-seasoning-solid" /></template>
