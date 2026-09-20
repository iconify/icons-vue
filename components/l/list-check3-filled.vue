<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgga4ebir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lgga4ebir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:list-check3-filled" /></template>
