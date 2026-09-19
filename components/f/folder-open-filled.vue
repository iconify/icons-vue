<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmb_z30dz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmb_z30dz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:folder-open-filled" /></template>
