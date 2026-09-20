<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgkz-7bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkz-7bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:activity-filled" /></template>
