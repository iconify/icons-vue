<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/si5ky56_s.css';
import '../../css/w/w-1mownrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si5ky56_s"/><path class="w-1mownrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:blood-test" /></template>
