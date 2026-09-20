<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp0qxs3rm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sp0qxs3rm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:add-square-fill" /></template>
