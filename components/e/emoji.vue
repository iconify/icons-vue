<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_eu7vqxz.css';
import '../../css/l/l-ctnfbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_eu7vqxz"/><path class="l-ctnfbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:emoji" /></template>
