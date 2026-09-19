<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wguh654wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wguh654wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:closet-filled" /></template>
