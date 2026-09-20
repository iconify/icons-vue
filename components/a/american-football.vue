<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj25bjbhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mj25bjbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:american-football" /></template>
