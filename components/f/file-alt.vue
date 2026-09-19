<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jjp3leb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="jjp3leb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-alt" /></template>
