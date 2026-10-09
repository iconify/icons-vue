<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgrnoabib.css';
import '../../css/k/kjish1bii.css';
import '../../css/l/l826gn27u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tgrnoabib"/><path class="kjish1bii"/><path class="l826gn27u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-full-20-bold" /></template>
