<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq7mjqbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dq7mjqbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:largebluediamond" /></template>
