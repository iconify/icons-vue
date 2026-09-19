<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl_bdxm0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yl_bdxm0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:component-tabs-filled" /></template>
