<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tua1clvxp.css';
import '../../css/i/imad5bjrh.css';
import '../../css/n/ngse4mb-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tua1clvxp"/><path class="imad5bjrh"/><path class="ngse4mb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chorizard-dark" /></template>
