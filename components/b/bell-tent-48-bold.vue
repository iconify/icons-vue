<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_2io1bvz.css';
import '../../css/t/tr-eedcjf.css';
import '../../css/o/o2ojfkh6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b_2io1bvz"/><path class="tr-eedcjf"/><path class="o2ojfkh6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bell-tent-48-bold" /></template>
