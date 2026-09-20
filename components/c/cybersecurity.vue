<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o20ksdzpf.css';
import '../../css/h/hbx3odb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o20ksdzpf"/><path class="hbx3odb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:cybersecurity" /></template>
