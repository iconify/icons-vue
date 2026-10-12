<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz3zj39wl.css';
import '../../css/m/m-jnejbbp.css';
import '../../css/f/fdgucpbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz3zj39wl"/><path clip-rule="evenodd" class="m-jnejbbp"/><path class="fdgucpbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:battery-plus-filled" /></template>
