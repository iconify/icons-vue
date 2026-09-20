<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl7tifc-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl7tifc-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flower-sharp-fill" /></template>
