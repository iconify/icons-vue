<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrwijsb_g.css';
import '../../css/t/t2wyy31bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vrwijsb_g"/><path class="t2wyy31bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:furniture-15" /></template>
