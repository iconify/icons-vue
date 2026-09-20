<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp3zz-bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp3zz-bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:font-awesome" /></template>
