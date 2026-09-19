<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duvzeob2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="duvzeob2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrows-split-up-and-left" /></template>
