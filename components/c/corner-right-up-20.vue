<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkc9nmf3a.css';
import '../../css/z/zosfd94fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gkc9nmf3a"/><path class="zosfd94fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-right-up-20" /></template>
