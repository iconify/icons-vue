<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxs_jpr0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxs_jpr0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:hashtag" /></template>
