<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb_ogzbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1027};
const content = `<path class="fb_ogzbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:alertpay" /></template>
