<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckuicm7cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckuicm7cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lgtm" /></template>
