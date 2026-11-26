<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr71nbcku.css';
import '../../css/p/p7p46pb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vr71nbcku"/><path class="p7p46pb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:codewars-wordmark" /></template>
