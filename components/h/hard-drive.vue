<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlhhir1qw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qlhhir1qw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:hard-drive" /></template>
