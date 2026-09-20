<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyu-xlb4c.css';
import '../../css/m/m1ot_8bgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyu-xlb4c"/><path clip-rule="evenodd" class="m1ot_8bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bao" /></template>
