<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuv-8rb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xuv-8rb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:facepunch" /></template>
