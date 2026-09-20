<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm97v_bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm97v_bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:corner-left-down-solid" /></template>
