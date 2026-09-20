<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du-lkubnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du-lkubnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:assistive-listening-systems" /></template>
