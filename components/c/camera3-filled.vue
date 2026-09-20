<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvk7_6bie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvk7_6bie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera3-filled" /></template>
