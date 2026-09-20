<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbdkfp3ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbdkfp3ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-up-light" /></template>
