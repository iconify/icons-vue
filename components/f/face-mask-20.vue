<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1y6bsbqe.css';
import '../../css/a/aldux5bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n1y6bsbqe"/><path class="aldux5bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:face-mask-20" /></template>
