<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uva2xdm3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uva2xdm3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:image-broken" /></template>
