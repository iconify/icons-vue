<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp767_blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp767_blx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:ban" /></template>
