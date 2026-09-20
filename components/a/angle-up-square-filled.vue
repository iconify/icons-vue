<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usm6v_bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="usm6v_bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:angle-up-square-filled" /></template>
