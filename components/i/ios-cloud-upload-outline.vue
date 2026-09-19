<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psgz5bp_u.css';
import '../../css/z/z3q3owb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="psgz5bp_u"/><path class="z3q3owb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-cloud-upload-outline" /></template>
