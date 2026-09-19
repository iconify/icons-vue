<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amezjz6vh.css';
import '../../css/a/a1eidib9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="amezjz6vh"/><path class="a1eidib9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:android-contact" /></template>
