<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xm81jd_my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xm81jd_my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:anchor" /></template>
