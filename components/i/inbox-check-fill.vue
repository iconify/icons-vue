<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee3miprbq.css';
import '../../css/y/yjr4r8bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee3miprbq"/><path class="yjr4r8bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:inbox-check-fill" /></template>
