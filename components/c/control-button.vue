<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogdkq6b9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ogdkq6b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:control-button" /></template>
