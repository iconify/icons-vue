<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jh10aebjc.css';
import '../../css/w/wo5yot8rw.css';
import '../../css/k/kz5dvk1mk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jh10aebjc"/><path class="wo5yot8rw"/><path class="kz5dvk1mk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ai-view" /></template>
