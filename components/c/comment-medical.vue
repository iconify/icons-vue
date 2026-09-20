<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc36aob7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xc36aob7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-medical" /></template>
