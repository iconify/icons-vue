<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haf8hxbsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haf8hxbsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:australiapost" /></template>
