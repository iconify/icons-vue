<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsl7p9qal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsl7p9qal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kakao" /></template>
