<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irm38m4_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irm38m4_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-1-filled" /></template>
