<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9qkw_60r.css';
import '../../css/a/aqfsfgwjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9qkw_60r"/><path class="aqfsfgwjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:dps" /></template>
