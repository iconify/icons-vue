<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er9_2_bjd.css';
import '../../css/d/du6sep0xm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er9_2_bjd"/><path clip-rule="evenodd" class="du6sep0xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-dot-outline" /></template>
