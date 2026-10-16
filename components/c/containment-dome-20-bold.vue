<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxuo0cziq.css';
import '../../css/y/yfoxxnbix.css';
import '../../css/q/qu5dliood.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxuo0cziq"/><path class="yfoxxnbix"/><path class="qu5dliood"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:containment-dome-20-bold" /></template>
