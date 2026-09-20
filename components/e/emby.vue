<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkv7bj1bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkv7bj1bg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:emby" /></template>
