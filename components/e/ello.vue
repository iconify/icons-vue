<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9y71hblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y9y71hblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:ello" /></template>
