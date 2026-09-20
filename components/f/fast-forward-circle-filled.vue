<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzn6ty5yb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzn6ty5yb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:fast-forward-circle-filled" /></template>
