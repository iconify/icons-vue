<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok1m3edsi.css';
import '../../css/b/b7_h5qb_d.css';
import '../../css/e/ehlm3jw4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ok1m3edsi"/><path class="b7_h5qb_d"/><path class="ehlm3jw4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:compost-48" /></template>
