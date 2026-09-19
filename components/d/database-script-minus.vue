<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlngh0wix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlngh0wix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:database-script-minus" /></template>
