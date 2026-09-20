<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn8pw1bah.css';
import '../../css/o/ooafjrbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn8pw1bah"/><path class="ooafjrbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-angry" /></template>
