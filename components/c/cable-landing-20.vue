<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd7xtmwmp.css';
import '../../css/v/v33j91b-f.css';
import '../../css/w/wo9nd_b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rd7xtmwmp"/><path class="v33j91b-f"/><path class="wo9nd_b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-landing-20" /></template>
