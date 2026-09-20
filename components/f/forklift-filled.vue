<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvn751v_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvn751v_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:forklift-filled" /></template>
