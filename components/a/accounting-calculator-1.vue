<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/be-3lv5bq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be-3lv5bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:accounting-calculator-1" /></template>
