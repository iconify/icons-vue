<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1z-b7k0t.css';
import '../../css/g/gnb4snbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1z-b7k0t"/><path class="gnb4snbyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:file-format-zip" /></template>
