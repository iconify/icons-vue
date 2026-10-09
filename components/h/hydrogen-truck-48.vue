<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xujk5fdpi.css';
import '../../css/x/x1dswctxk.css';
import '../../css/z/zjk_4wbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xujk5fdpi"/><path class="x1dswctxk"/><path class="zjk_4wbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydrogen-truck-48" /></template>
