<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inog0fb6a.css';
import '../../css/a/axk7hmbie.css';
import '../../css/l/l7unjebct.css';
import '../../css/y/y_rvfmb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="inog0fb6a"/><path class="axk7hmbie"/><path class="l7unjebct"/><path class="y_rvfmb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fuel-oil-tank-20" /></template>
