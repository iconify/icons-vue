<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/asbqrgbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asbqrgbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:grip" /></template>
