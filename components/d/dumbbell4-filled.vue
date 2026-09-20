<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by58ksbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by58ksbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:dumbbell4-filled" /></template>
