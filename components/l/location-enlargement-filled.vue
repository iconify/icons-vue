<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_v_495xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_v_495xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location-enlargement-filled" /></template>
