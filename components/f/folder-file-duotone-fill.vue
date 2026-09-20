<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7zwtsbyj.css';
import '../../css/m/mch1fnkdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="d7zwtsbyj"/><path class="mch1fnkdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-file-duotone-fill" /></template>
