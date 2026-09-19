<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cb_i9scyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":960};
const content = `<path class="cb_i9scyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circleloadertwo" /></template>
