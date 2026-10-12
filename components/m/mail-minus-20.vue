<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndihgzbwa.css';
import '../../css/a/awn7h3b2c.css';
import '../../css/z/zkdyo_ief.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ndihgzbwa"/><path class="awn7h3b2c"/><path class="zkdyo_ief"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-minus-20" /></template>
