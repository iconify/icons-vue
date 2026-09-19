<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbsiz1bro.css';
import '../../css/j/jt_ac1zjj.css';
import '../../css/c/c5zqg9bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="fbsiz1bro"/><path class="jt_ac1zjj"/><path class="c5zqg9bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:bg-4x3" /></template>
