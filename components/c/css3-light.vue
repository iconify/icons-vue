<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqn4acquj.css';
import '../../css/v/vr6lccbrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqn4acquj"/><path class="vr6lccbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:css3-light" /></template>
