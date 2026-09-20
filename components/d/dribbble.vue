<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5qx8cb0r.css';
import '../../css/a/aycg7s_1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="h5qx8cb0r"/><path class="aycg7s_1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:dribbble" /></template>
