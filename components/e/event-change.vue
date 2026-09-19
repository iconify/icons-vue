<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmkiuqb-h.css';
import '../../css/i/icpcz1bju.css';
import '../../css/g/gah67z6_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mmkiuqb-h"/><circle class="icpcz1bju"/><path class="gah67z6_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:event-change" /></template>
