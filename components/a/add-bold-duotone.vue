<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaoyf82ot.css';
import '../../css/v/vmj_u5b4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaoyf82ot"/><path class="vmj_u5b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:add-bold-duotone" /></template>
