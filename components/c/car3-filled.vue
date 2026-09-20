<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lefryqbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lefryqbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:car3-filled" /></template>
