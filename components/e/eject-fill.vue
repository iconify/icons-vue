<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oth-gwbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oth-gwbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:eject-fill" /></template>
