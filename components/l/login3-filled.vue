<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abqt2_evv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abqt2_evv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:login3-filled" /></template>
