<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ojc2h6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9ojc2h6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dropbox-fill" /></template>
