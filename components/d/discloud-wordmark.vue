<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydv6ohbun.css';
import '../../css/g/g-mfsnbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ydv6ohbun"/><path class="g-mfsnbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:discloud-wordmark" /></template>
