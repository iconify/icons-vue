<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj_-u5bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj_-u5bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-up" /></template>
