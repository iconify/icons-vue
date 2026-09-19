<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3djcx2jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u3djcx2jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-flag" /></template>
