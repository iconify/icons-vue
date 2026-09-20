<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmfrhpbbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmfrhpbbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:amazon-clouddrive" /></template>
