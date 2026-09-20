<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auk_w91qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auk_w91qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comparison" /></template>
