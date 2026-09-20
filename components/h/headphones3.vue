<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcmi_-bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcmi_-bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:headphones3" /></template>
