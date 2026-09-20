<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_wlz3bgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_wlz3bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:dollar-sign-duotone" /></template>
