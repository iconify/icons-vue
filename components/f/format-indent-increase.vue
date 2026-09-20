<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck__t7yhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck__t7yhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-indent-increase" /></template>
