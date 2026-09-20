<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mujznmb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mujznmb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:logout2" /></template>
