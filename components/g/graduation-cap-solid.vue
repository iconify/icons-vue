<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx6-67b-c.css';
import '../../css/h/hk-cwxbdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nx6-67b-c"/><path class="hk-cwxbdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:graduation-cap-solid" /></template>
