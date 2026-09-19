<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxnslnd9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxnslnd9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:arrows-breake-h" /></template>
