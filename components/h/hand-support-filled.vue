<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk-i4_xvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wk-i4_xvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hand-support-filled" /></template>
