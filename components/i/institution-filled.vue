<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi7qo4bfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7qo4bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:institution-filled" /></template>
