<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkz-nvrhb.css';
import '../../css/y/ypfowt0pb.css';
import '../../css/f/f8imsv3ke.css';
import '../../css/y/y7nehvo7v.css';
import '../../css/y/y1ys-0bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="rkz-nvrhb"/><path class="ypfowt0pb"/><path class="f8imsv3ke"/><path class="y7nehvo7v"/><path class="y1ys-0bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:almalinux" /></template>
