<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd4m4tkzl.css';
import '../../css/e/ebd7f4inr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd4m4tkzl"/><path class="ebd7f4inr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:android-alt" /></template>
