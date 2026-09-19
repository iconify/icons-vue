<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2-j6pbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f2-j6pbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:archlinux" /></template>
