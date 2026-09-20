<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sko-q4bya.css';
import '../../css/w/ww5a72t8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sko-q4bya"/><path class="ww5a72t8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:delete-time-filled" /></template>
