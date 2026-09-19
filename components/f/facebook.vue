<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxndvphjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":1024};
const content = `<path class="dxndvphjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:facebook" /></template>
