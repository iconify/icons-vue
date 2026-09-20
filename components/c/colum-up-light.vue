<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brzsx4jtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brzsx4jtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:colum-up-light" /></template>
