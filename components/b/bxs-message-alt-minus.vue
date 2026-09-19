<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9hzpsuyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9hzpsuyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-message-alt-minus" /></template>
