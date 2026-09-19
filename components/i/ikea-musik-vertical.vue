<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dob6lsbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dob6lsbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-musik-vertical" /></template>
