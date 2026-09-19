<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9npbdcjc.css';
import '../../css/d/d8axicc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9npbdcjc"/><path class="d8axicc0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:instagram" /></template>
