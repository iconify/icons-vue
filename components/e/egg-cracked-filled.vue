<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xatgpdb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xatgpdb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:egg-cracked-filled" /></template>
