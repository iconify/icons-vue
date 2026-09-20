<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk7fr0_yu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yk7fr0_yu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:american-sign-language-interpreting-solid" /></template>
