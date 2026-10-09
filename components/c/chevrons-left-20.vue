<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_7y3qb_r.css';
import '../../css/h/hrdk82bep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_7y3qb_r"/><path class="hrdk82bep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chevrons-left-20" /></template>
