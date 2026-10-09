<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htffp3b5a.css';
import '../../css/q/qu-izxe2j.css';
import '../../css/f/fsc5e1bho.css';
import '../../css/f/fqrraspid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="htffp3b5a"/><path class="qu-izxe2j"/><path class="fsc5e1bho"/><path class="fqrraspid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-car-20" /></template>
