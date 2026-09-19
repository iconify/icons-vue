<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw9lnybso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":880,"height":614};
const content = `<path class="qw9lnybso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:digg" /></template>
