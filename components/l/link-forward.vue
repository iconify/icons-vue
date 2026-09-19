<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uac40eb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uac40eb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:link-forward" /></template>
