<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yupvxm31u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="yupvxm31u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:keyboard-hide" /></template>
