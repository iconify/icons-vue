<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnv98eadn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnv98eadn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:inbox-out-alt-filled" /></template>
