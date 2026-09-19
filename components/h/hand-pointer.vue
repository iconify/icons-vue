<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymxomjbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ymxomjbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hand-pointer" /></template>
