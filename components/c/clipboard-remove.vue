<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsmf7uamc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lsmf7uamc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-remove" /></template>
