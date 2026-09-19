<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpoubbo_e.css';
import '../../css/k/k70t2o__t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpoubbo_e"/><path class="k70t2o__t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dice-1" /></template>
