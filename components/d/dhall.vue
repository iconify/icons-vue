<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el0u0wbjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":243,"height":512};
const content = `<path class="el0u0wbjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dhall" /></template>
