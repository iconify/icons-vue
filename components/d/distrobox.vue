<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn5_h39-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn5_h39-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:distrobox" /></template>
