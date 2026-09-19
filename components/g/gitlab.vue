<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xui0s0b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xui0s0b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gitlab" /></template>
