<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9w7oc8rl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9w7oc8rl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:homarr" /></template>
