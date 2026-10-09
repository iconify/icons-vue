<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyr9-qb4r.css';
import '../../css/f/fcdrigb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dyr9-qb4r"/><path class="fcdrigb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crucible-20" /></template>
