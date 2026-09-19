<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztd26o_pc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ztd26o_pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:inbox-in-alt-filled" /></template>
