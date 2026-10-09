<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_x1_pbed.css';
import '../../css/s/sf-hyccxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="v_x1_pbed"/><path class="sf-hyccxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:kettle-20" /></template>
