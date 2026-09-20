<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck-rj9bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-rj9bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-hiflow" /></template>
