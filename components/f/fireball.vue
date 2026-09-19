<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqb2svp2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqb2svp2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:fireball" /></template>
