<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkh-r-d0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkh-r-d0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:fast-backward-filled" /></template>
