<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk7s-5bkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wk7s-5bkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-checks-duotone" /></template>
