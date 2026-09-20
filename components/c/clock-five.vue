<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_44q3bqb.css';
import '../../css/c/chv7bcx-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_44q3bqb"/><path class="chv7bcx-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:clock-five" /></template>
