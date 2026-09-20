<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuksi0y_p.css';
import '../../css/w/ww5a72t8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fuksi0y_p"/><path class="ww5a72t8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:lock-time-filled" /></template>
