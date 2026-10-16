<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onn6syb7h.css';
import '../../css/z/z6nk_cc1b.css';
import '../../css/c/c9a_4u5us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onn6syb7h"/><path class="z6nk_cc1b"/><path class="c9a_4u5us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:iot-device-20" /></template>
