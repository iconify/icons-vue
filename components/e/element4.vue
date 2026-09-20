<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_nwxbb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_nwxbb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:element4" /></template>
