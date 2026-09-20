<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un0prhb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="un0prhb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:checkmark" /></template>
