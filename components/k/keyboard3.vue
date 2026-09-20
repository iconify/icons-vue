<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgajv3ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgajv3ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:keyboard3" /></template>
