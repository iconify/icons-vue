<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwm-t2b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pwm-t2b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:image-broken" /></template>
