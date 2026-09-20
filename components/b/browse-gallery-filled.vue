<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1asp8k8y.css';
import '../../css/m/moh8knr5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1asp8k8y"/><path class="moh8knr5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:browse-gallery-filled" /></template>
