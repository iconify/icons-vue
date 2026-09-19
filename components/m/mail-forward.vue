<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2mrd7ini.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2mrd7ini"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:mail-forward" /></template>
