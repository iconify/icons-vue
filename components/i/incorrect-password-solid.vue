<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uoix2j7si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uoix2j7si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:incorrect-password-solid" /></template>
