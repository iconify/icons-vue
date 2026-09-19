<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b04z-5r7l.css';
import '../../css/h/h848uabup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b04z-5r7l"/><path class="h848uabup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bandage" /></template>
