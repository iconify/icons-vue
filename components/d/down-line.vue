<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-zdqbcgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-zdqbcgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:down-line" /></template>
