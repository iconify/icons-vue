<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh-430moi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh-430moi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:course-up-broken" /></template>
