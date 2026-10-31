<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyah5ibdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyah5ibdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:instagram-round" /></template>
