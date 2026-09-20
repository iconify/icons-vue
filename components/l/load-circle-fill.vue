<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inx9gng5o.css';
import '../../css/w/wrhz-zbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inx9gng5o"/><path class="wrhz-zbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:load-circle-fill" /></template>
