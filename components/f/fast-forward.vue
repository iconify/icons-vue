<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9-n5-bxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1,"top":-3};
const content = `<path class="t9-n5-bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fast-forward" /></template>
