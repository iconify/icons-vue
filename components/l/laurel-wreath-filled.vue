<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvby8_i7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvby8_i7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laurel-wreath-filled" /></template>
