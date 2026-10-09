<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ensv1cbds.css';
import '../../css/c/cgbp4zbep.css';
import '../../css/g/gm5d6ob0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ensv1cbds"/><path class="cgbp4zbep"/><path class="gm5d6ob0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charger-fault-20-bold" /></template>
