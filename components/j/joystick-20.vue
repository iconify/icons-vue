<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irh_wpbqi.css';
import '../../css/t/t_i7wlb6k.css';
import '../../css/e/e71fuis0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="irh_wpbqi"/><path class="t_i7wlb6k"/><path class="e71fuis0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:joystick-20" /></template>
