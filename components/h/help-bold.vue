<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw5g050oe.css';
import '../../css/w/w19abnbit.css';
import '../../css/t/tsguwswfn.css';
import '../../css/a/ae2knfujf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw5g050oe"/><path class="w19abnbit"/><path class="tsguwswfn"/><path class="ae2knfujf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:help-bold" /></template>
