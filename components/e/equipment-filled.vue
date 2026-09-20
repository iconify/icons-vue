<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gam_9d_az.css';
import '../../css/l/lqted7wxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gam_9d_az"/><path clip-rule="evenodd" class="lqted7wxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:equipment-filled" /></template>
