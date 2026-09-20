<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zuww5n5ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuww5n5ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:euro2-filled" /></template>
