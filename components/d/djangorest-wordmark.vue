<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzxe0-1un.css';
import '../../css/h/h84axl_8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zzxe0-1un"/><path class="h84axl_8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:djangorest-wordmark" /></template>
