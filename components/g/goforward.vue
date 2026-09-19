<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dih2-uk2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="dih2-uk2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:goforward" /></template>
