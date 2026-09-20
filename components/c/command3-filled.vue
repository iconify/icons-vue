<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-6j-kcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zw-6j-kcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:command3-filled" /></template>
