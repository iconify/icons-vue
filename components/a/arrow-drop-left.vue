<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa6d_acfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa6d_acfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:arrow-drop-left" /></template>
