<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz-ewac9b.css';
import '../../css/c/c-39a_bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz-ewac9b"/><path class="c-39a_bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:automl-vision" /></template>
