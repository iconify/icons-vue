<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdi64yb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-4};
const content = `<path class="gdi64yb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:gamepad" /></template>
