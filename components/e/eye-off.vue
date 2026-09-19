<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng5pp8tbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng5pp8tbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:eye-off" /></template>
