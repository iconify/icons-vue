<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc4op3bci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc4op3bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:expand-vertical" /></template>
